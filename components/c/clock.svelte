<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3eo2xxnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="m3eo2xxnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:clock" {...props}></Icon>
