<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pekzi00tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="pekzi00tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:ninja" {...props}></Icon>
