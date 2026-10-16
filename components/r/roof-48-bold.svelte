<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2mlpnqnh.css';
import '../../css/d/d7knfxo3n.css';
import '../../css/k/kbe1bit3g.css';
import '../../css/p/pne_1mbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f2mlpnqnh"/><path class="d7knfxo3n"/><path class="kbe1bit3g"/><path class="pne_1mbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:roof-48-bold" {...props}></Icon>
