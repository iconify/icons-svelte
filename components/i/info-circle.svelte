<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aqsexabqu.css';
import '../../css/v/v6zwtfsnc.css';
import '../../css/w/wqaq_tblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="aqsexabqu"/><circle class="v6zwtfsnc"/><path clip-rule="evenodd" class="wqaq_tblz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:info-circle" {...props}></Icon>
