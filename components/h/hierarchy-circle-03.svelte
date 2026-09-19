<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e842h2b0v.css';
import '../../css/f/fwi1i6brr.css';
import '../../css/u/uukfrxkmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e842h2b0v"/><path class="fwi1i6brr"/><path class="uukfrxkmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hierarchy-circle-03" {...props}></Icon>
