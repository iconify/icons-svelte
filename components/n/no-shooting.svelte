<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/g-jwhsbbd.css';
import '../../css/m/mbe_9obgv.css';
import '../../css/i/igso98b1i.css';
import '../../css/h/hwdijdbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="g-jwhsbbd"/><path class="mbe_9obgv"/><path class="igso98b1i"/><circle class="hwdijdbgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:no-shooting" {...props}></Icon>
