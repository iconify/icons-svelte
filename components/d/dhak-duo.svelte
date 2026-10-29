<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nzqc28bzy.css';
import '../../css/d/d8m5d21rd.css';
import '../../css/l/lq_cp1bfu.css';
import '../../css/d/dp9ap3b7v.css';
import '../../css/y/ywgqm0b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nzqc28bzy"/><path class="d8m5d21rd wm-a"/><path class="lq_cp1bfu"/><path class="dp9ap3b7v"/><path class="wm-a ywgqm0b7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dhak-duo" {...props}></Icon>
