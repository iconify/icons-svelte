<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mtqifvxek.css';
import '../../css/g/gq4bevilf.css';
import '../../css/n/ngbgmgbhh.css';
import '../../css/p/phoc4kb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mtqifvxek"/><path class="gq4bevilf wm-a"/><path class="ngbgmgbhh wm-k"/><path class="phoc4kb0a wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:headset-sketch" {...props}></Icon>
