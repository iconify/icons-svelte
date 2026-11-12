<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdtzqfxwt.css';
import '../../css/t/tx9vi1y_m.css';
import '../../css/t/tr7cg_bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mdtzqfxwt"/><path class="tx9vi1y_m"/><path class="tr7cg_bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dawarich-light" {...props}></Icon>
