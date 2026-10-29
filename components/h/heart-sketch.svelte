<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n20stxzlo.css';
import '../../css/r/r6wr3hswm.css';
import '../../css/b/bwhpywb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n20stxzlo"/><path class="r6wr3hswm"/><path class="bwhpywb7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-sketch" {...props}></Icon>
