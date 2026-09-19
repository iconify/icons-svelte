<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rggfaqb6e.css';
import '../../css/w/wrb5chb2g.css';
import '../../css/w/wbdap1rkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rggfaqb6e"><path class="wrb5chb2g"/><path class="wbdap1rkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:arrow-left" {...props}></Icon>
