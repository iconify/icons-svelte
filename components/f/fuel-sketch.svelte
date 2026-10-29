<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/juj-yyb3h.css';
import '../../css/r/ryv0a7boy.css';
import '../../css/d/drhbokbsz.css';
import '../../css/n/nu6fsptef.css';
import '../../css/c/ci-xzcbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="juj-yyb3h"/><path class="ryv0a7boy wm-k"/><path class="drhbokbsz wm-a"/><path class="nu6fsptef wm-k"/><path class="ci-xzcbit wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fuel-sketch" {...props}></Icon>
