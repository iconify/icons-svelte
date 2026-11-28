<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tun7kpbmr.css';
import '../../css/a/a2uaf5emu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tun7kpbmr"/><path class="a2uaf5emu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-duo" {...props}></Icon>
