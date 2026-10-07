<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfxp86bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfxp86bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:airplane-off" {...props}></Icon>
