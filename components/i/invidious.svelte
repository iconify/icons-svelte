<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxvcavblc.css';
import '../../css/x/xy40cepxe.css';
import '../../css/e/exoxidbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gxvcavblc"/><path class="xy40cepxe"/><path class="exoxidbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invidious" {...props}></Icon>
