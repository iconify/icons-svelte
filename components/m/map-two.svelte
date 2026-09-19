<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/uzu-zgn4d.css';
import '../../css/y/y4761y4co.css';
import '../../css/r/r9sywpbmq.css';
import '../../css/h/hqqlb8bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="uzu-zgn4d"/><path class="y4761y4co"/><path class="r9sywpbmq"/><path class="hqqlb8bcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:map-two" {...props}></Icon>
