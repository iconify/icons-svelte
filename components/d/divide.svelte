<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw2um-8au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="dw2um-8au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:divide" {...props}></Icon>
