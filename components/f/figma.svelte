<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lk3a4_bsk.css';
import '../../css/x/xdr5wfo2x.css';
import '../../css/j/jpt088bte.css';
import '../../css/x/xvcvy83wb.css';
import '../../css/f/f-z0o8b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lk3a4_bsk"/><path class="xdr5wfo2x"/><path class="jpt088bte"/><path class="xvcvy83wb"/><path class="f-z0o8b2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:figma" {...props}></Icon>
