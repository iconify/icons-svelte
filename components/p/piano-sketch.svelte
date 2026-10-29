<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r-bsq-m3v.css';
import '../../css/k/kqraa7qvj.css';
import '../../css/r/r0m-rx3lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r-bsq-m3v wm-k"/><path class="kqraa7qvj wm-k"/><path class="r0m-rx3lk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:piano-sketch" {...props}></Icon>
