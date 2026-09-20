<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj1uad_0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nj1uad_0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockprobe-dark" {...props}></Icon>
