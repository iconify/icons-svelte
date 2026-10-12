<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/es55_xboo.css';
import '../../css/c/cfupnld-v.css';
import '../../css/w/wde-mrlcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="es55_xboo"/><path class="cfupnld-v"/><path class="wde-mrlcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-dot-duotone" {...props}></Icon>
