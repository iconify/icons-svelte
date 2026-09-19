<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv1w6dbgf.css';
import '../../css/y/yglam5kqs.css';
import '../../css/v/vqeh6flxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv1w6dbgf"/><path class="yglam5kqs"/><circle class="vqeh6flxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-speaker" {...props}></Icon>
