<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6w23hbvq.css';
import '../../css/l/luh2gib-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6w23hbvq"/><path class="luh2gib-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-desktop" {...props}></Icon>
