<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h_qzm70hz.css';
import '../../css/v/vtr87b2ik.css';
import '../../css/c/cllgogb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h_qzm70hz"/><path class="vtr87b2ik"/><path clip-rule="evenodd" class="cllgogb_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:binoculars-bold" {...props}></Icon>
