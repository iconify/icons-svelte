<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpazd_-xr.css';
import '../../css/t/tnu5vf6mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpazd_-xr"/><path class="tnu5vf6mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onetime-secret" {...props}></Icon>
