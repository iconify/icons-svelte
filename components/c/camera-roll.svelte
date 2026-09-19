<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duwc1vbbx.css';
import '../../css/w/w9p-hib0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="duwc1vbbx"/><path class="w9p-hib0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:camera-roll" {...props}></Icon>
