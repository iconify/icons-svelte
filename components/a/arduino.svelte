<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sto5bkbur.css';
import '../../css/y/yrmlhdbfc.css';
import '../../css/e/ep-2nyeek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="sto5bkbur"><path class="yrmlhdbfc"/><path class="ep-2nyeek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:arduino" {...props}></Icon>
