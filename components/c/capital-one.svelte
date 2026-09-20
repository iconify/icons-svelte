<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy8_nmbyv.css';
import '../../css/c/c7mlw_bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":418,"height":150};
const content = `<path class="xy8_nmbyv"/><path class="c7mlw_bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:capital-one" {...props}></Icon>
