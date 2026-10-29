<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/ok2h6kb5u.css';
import '../../css/k/kctmd-b-w.css';
import '../../css/b/bvody_b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ok2h6kb5u"/><path class="kctmd-b-w wm-k"/><path class="bvody_b8k wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cpu-sketch" {...props}></Icon>
