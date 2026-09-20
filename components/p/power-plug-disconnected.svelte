<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxnsjwbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxnsjwbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:power-plug-disconnected" {...props}></Icon>
