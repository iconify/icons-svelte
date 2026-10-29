<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/em-dy2t7x.css';
import '../../css/b/b-17occjh.css';
import '../../css/b/bkprrvblz.css';
import '../../css/k/kq4anp9be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="em-dy2t7x"/><path class="b-17occjh wm-a"/><path class="bkprrvblz wm-k"/><path class="kq4anp9be wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:globe-sketch" {...props}></Icon>
