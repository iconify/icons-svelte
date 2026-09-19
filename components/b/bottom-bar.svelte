<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/l/l88i7dblt.css';
import '../../css/g/gfrclwb4b.css';
import '../../css/y/yi6bw9bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="l88i7dblt"/><path class="gfrclwb4b"/><path class="yi6bw9bpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bottom-bar" {...props}></Icon>
