<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/leetrzeag.css';
import '../../css/i/ih39qpbch.css';
import '../../css/y/yjgegjbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="leetrzeag wm-a"/><path class="ih39qpbch wm-k"/><path class="wm-a yjgegjbzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:battery-medium-sketch" {...props}></Icon>
