<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yzgi8xb4w.css';
import '../../css/o/ov9ho64it.css';
import '../../css/d/disb1cb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-a yzgi8xb4w"/><path class="ov9ho64it wm-k"/><path class="disb1cb5z wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-network-sketch" {...props}></Icon>
