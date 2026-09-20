<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-sfxobwe.css';
import '../../css/t/tg-9ed7zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-sfxobwe"/><path class="tg-9ed7zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-vpn-light" {...props}></Icon>
