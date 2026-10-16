<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etlms99xu.css';
import '../../css/p/pzppjacqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="etlms99xu"/><path class="pzppjacqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-hydro-48-bold" {...props}></Icon>
