<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d62hrbclj.css';
import '../../css/t/t2g4dfbck.css';
import '../../css/i/isq34acxh.css';
import '../../css/x/x-e655bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d62hrbclj wm-k"/><path class="t2g4dfbck wm-k"/><path class="isq34acxh wm-k"/><path class="wm-shine x-e655bfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:minus" {...props}></Icon>
