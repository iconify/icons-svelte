<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jc4l4pbqy.css';
import '../../css/o/ollzt4brz.css';
import '../../css/x/xgz_75bxv.css';
import '../../css/j/ja9zyxbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jc4l4pbqy"/><path class="ollzt4brz wm-a"/><path class="wm-k xgz_75bxv"/><path class="ja9zyxbzw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:grape-sketch" {...props}></Icon>
