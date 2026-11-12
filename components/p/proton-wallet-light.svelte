<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dne8y0bds.css';
import '../../css/b/b1ivybqei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dne8y0bds"/><path class="b1ivybqei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-wallet-light" {...props}></Icon>
