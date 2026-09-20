<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgh7emwcy.css';
import '../../css/x/xxyq6_bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgh7emwcy"/><path class="xxyq6_bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-mail-bridge-dark" {...props}></Icon>
