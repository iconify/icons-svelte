<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uzcqkeblz.css';
import '../../css/a/awnu8db8z.css';
import '../../css/x/xd7rb_b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uzcqkeblz wm-k"/><path class="awnu8db8z wm-k"/><path class="wm-a xd7rb_b1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:puja-thali-sketch" {...props}></Icon>
