<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lpr_75b6j.css';
import '../../css/h/hd4103b_c.css';
import '../../css/v/v83p6u1bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="lpr_75b6j"/><path class="hd4103b_c"/><path class="v83p6u1bx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-16" {...props}></Icon>
