<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/q/q3tvm8bbi.css';
import '../../css/o/oz0g4by4m.css';
import '../../css/h/hzarsdbal.css';
import '../../css/r/r9d8tnb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="q3tvm8bbi"/><path class="oz0g4by4m"/><path class="hzarsdbal"/><path class="r9d8tnb2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:bell-off" {...props}></Icon>
