<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qtx3gwboz.css';
import '../../css/h/hw4w3wbpy.css';
import '../../css/c/c0jlas_ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qtx3gwboz"/><path class="hw4w3wbpy wm-k"/><path class="c0jlas_ay wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-bunny-sketch" {...props}></Icon>
