<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/d/dyone_blp.css';
import '../../css/q/q-em7j0jk.css';
import '../../css/g/gi9trt-rw.css';
import '../../css/q/qy_qwjbnq.css';
import '../../css/x/xq4ykab6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="dyone_blp"/><ellipse class="q-em7j0jk"/><path class="gi9trt-rw"/><ellipse class="qy_qwjbnq"/><path class="xq4ykab6k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:music" {...props}></Icon>
