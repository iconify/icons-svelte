<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cgf36yvjm.css';
import '../../css/f/fr09pvb7p.css';
import '../../css/k/kr0s17gbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cgf36yvjm"/><path class="fr09pvb7p wm-k"/><path class="kr0s17gbf wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-lock-sketch" {...props}></Icon>
