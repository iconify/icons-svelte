<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qnnc6fbcv.css';
import '../../css/j/jox8k1brk.css';
import '../../css/y/ytth9f11g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qnnc6fbcv wm-k"/><path class="jox8k1brk wm-shine"/><path class="wm-shine ytth9f11g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:receipt-text" {...props}></Icon>
