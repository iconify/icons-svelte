<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv5hqibas.css';
import '../../css/b/b1ivybqei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fv5hqibas"/><path class="b1ivybqei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-wallet-light" {...props}></Icon>
