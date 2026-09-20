<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eb2wkrbqz.css';
import '../../css/v/v70sv_b8n.css';
import '../../css/c/c41kgs53a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eb2wkrbqz"/><path class="v70sv_b8n"/><path clip-rule="evenodd" class="c41kgs53a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:accumulator-filled" {...props}></Icon>
