<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gdzci1beo.css';
import '../../css/s/sd2p3fbaq.css';
import '../../css/h/h7iic-bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gdzci1beo"/><path class="sd2p3fbaq wm-k"/><path class="h7iic-bcm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:projector-sketch" {...props}></Icon>
