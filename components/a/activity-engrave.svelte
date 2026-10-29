<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a471k1qjf.css';
import '../../css/f/f2uc4dbbl.css';
import '../../css/v/v53283b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a471k1qjf"/><path class="f2uc4dbbl wm-shadow"/><path class="v53283b0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:activity-engrave" {...props}></Icon>
