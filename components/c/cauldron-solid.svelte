<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/v5dqb5lav.css';
import '../../css/e/e7o0z2bsq.css';
import '../../css/k/kzd_5m5vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="v5dqb5lav"/><path class="e7o0z2bsq wm-a"/><path class="kzd_5m5vf wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cauldron-solid" {...props}></Icon>
