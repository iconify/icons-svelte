<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaw58obxy.css';
import '../../css/g/g90zm0rma.css';
import '../../css/u/uvvyx1dtx.css';
import '../../css/e/eys1nnoqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="uaw58obxy"><path class="g90zm0rma"/><path class="uvvyx1dtx"/><path class="eys1nnoqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:filter-one" {...props}></Icon>
