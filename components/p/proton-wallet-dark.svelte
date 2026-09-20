<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy8db6b8d.css';
import '../../css/k/kch4ro44n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xy8db6b8d"/><path class="kch4ro44n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-wallet-dark" {...props}></Icon>
