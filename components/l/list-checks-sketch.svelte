<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f1b9shfss.css';
import '../../css/z/zomf0k0wi.css';
import '../../css/l/l94wqzpmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f1b9shfss wm-k"/><path class="wm-k zomf0k0wi"/><path class="l94wqzpmb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-checks-sketch" {...props}></Icon>
