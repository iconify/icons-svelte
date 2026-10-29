<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/us4l7n-bh.css';
import '../../css/v/v4goc3b9j.css';
import '../../css/t/th46yjuif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="us4l7n-bh"/><path class="v4goc3b9j wm-k"/><path class="th46yjuif wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-play-sketch" {...props}></Icon>
