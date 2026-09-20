<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzg19p0qh.css';
import '../../css/f/f2eh-dbua.css';
import '../../css/a/aca60mb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzg19p0qh"/><path class="f2eh-dbua"/><path class="aca60mb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-alerts-dashboard-light" {...props}></Icon>
