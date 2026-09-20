<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/n/nj69sobsr.css';
import '../../css/o/oy8-2ebuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 3)" class="jtowsomii"><path class="nj69sobsr"/><circle class="oy8-2ebuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:nut" {...props}></Icon>
