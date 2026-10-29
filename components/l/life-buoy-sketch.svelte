<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m05ok2q9c.css';
import '../../css/i/i84v56bxz.css';
import '../../css/k/k808-jbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m05ok2q9c"/><path class="i84v56bxz wm-k"/><path class="k808-jbxa wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:life-buoy-sketch" {...props}></Icon>
