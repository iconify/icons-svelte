<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyg-aubic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="vyg-aubic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:delta" {...props}></Icon>
