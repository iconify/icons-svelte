<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/j/jdyuftccb.css';
import '../../css/e/ekm30-jss.css';
import '../../css/v/v27l2fbxo.css';
import '../../css/p/p2pw0cbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="jdyuftccb"/><rect class="ekm30-jss"/><path class="v27l2fbxo"/><path clip-rule="evenodd" class="p2pw0cbcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:fan-option" {...props}></Icon>
