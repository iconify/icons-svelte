<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swfgeb0ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="swfgeb0ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:bluetooth" {...props}></Icon>
