<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crd2je-4i.css';
import '../../css/f/fxwwtlavh.css';
import '../../css/q/qkrmpnbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crd2je-4i"/><path class="fxwwtlavh"/><path class="qkrmpnbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnet-bold" {...props}></Icon>
