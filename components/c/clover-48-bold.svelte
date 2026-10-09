<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fginnxrdt.css';
import '../../css/m/mpfbstbhm.css';
import '../../css/w/wn32g0bsf.css';
import '../../css/d/d4x_2oiju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fginnxrdt"/><path class="mpfbstbhm"/><path class="wn32g0bsf"/><path class="d4x_2oiju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clover-48-bold" {...props}></Icon>
