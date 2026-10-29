<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l1wls693y.css';
import '../../css/i/i-ml486ue.css';
import '../../css/d/dmqvzwbzf.css';
import '../../css/o/oida52bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l1wls693y wm-k"/><path class="i-ml486ue wm-a"/><path class="dmqvzwbzf wm-k"/><path class="oida52bfh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:link-sketch" {...props}></Icon>
