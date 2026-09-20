<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgw-p5f4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgw-p5f4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:airplane-train" {...props}></Icon>
