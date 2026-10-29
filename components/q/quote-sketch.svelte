<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j9nhecbga.css';
import '../../css/x/xnrpwftli.css';
import '../../css/v/vrcorib2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j9nhecbga"/><path class="xnrpwftli"/><path class="vrcorib2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:quote-sketch" {...props}></Icon>
