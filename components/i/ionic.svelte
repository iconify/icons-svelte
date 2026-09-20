<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfnlz1bwm.css';
import '../../css/y/yvav3etyo.css';
import '../../css/k/kx7lj1yvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="jfnlz1bwm"><path class="yvav3etyo"/><circle class="kx7lj1yvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ionic" {...props}></Icon>
