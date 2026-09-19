<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xwh7h2bfx.css';
import '../../css/g/g8e35kbyv.css';
import '../../css/y/yv76jrb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="xwh7h2bfx"/><path class="g8e35kbyv"/><path class="yv76jrb0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:cones" {...props}></Icon>
