<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ic523acqq.css';
import '../../css/v/vr012vb-l.css';
import '../../css/x/xklaxdbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ic523acqq"/><path class="vr012vb-l"/><path class="xklaxdbny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:microphone-slash" {...props}></Icon>
