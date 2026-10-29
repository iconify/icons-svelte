<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r-ye7do_q.css';
import '../../css/j/j9w0z1j2s.css';
import '../../css/f/fwj0tvb2f.css';
import '../../css/d/dsl3x27ur.css';
import '../../css/f/ffez6rw7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r-ye7do_q"/><path class="j9w0z1j2s wm-k"/><path class="fwj0tvb2f wm-a"/><path class="dsl3x27ur wm-k"/><path class="ffez6rw7v wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bird-sketch" {...props}></Icon>
