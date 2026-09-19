<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/z1p5pfbgn.css';
import '../../css/l/lcd2nmarj.css';
import '../../css/x/xhce_hbyg.css';
import '../../css/h/hamkaq0zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="z1p5pfbgn"/><path class="lcd2nmarj"/><path class="xhce_hbyg"/><path class="hamkaq0zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-11" {...props}></Icon>
