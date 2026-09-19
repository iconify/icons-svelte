<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0yfrvl6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w0yfrvl6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rocket-stroke-16" {...props}></Icon>
