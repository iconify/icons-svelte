<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvgpuebcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvgpuebcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:decimal-increase" {...props}></Icon>
