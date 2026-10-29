<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fpcuoqb7g.css';
import '../../css/v/v7npj_bxk.css';
import '../../css/x/xmzujebsj.css';
import '../../css/n/nn2sdrbun.css';
import '../../css/x/xfyuoc22x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fpcuoqb7g wm-k"/><path class="v7npj_bxk wm-a"/><path class="wm-shadow xmzujebsj"/><path class="nn2sdrbun wm-k"/><path class="wm-a xfyuoc22x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:battery-medium-engrave" {...props}></Icon>
