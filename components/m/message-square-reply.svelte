<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/ls2l-iphu.css';
import '../../css/r/rvcd_fbtv.css';
import '../../css/z/zptexebry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ls2l-iphu"/><path class="rvcd_fbtv"/><path class="zptexebry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-square-reply" {...props}></Icon>
