<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbn6v7b5m.css';
import '../../css/z/zd_hbsbad.css';
import '../../css/r/rp7oy-b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nbn6v7b5m"/><path class="zd_hbsbad"/><path class="rp7oy-b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:finn-light" {...props}></Icon>
