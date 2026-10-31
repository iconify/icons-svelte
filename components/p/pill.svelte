<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/y/yrce0dx3b.css';
import '../../css/e/ey58x5bil.css';
import '../../css/k/kp5upqfdx.css';
import '../../css/v/vg2dcxbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow yrce0dx3b"/><path class="ey58x5bil wm-shadow"/><path class="kp5upqfdx"/><path class="vg2dcxbfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:pill" {...props}></Icon>
