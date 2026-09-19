<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l47qxzfbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":480};
const content = `<path class="l47qxzfbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:refresh" {...props}></Icon>
