<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzg19p0qh.css';
import '../../css/q/q8n-7fbhw.css';
import '../../css/g/gy63hpboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzg19p0qh"/><path class="q8n-7fbhw"/><path class="gy63hpboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-alerts-dashboard-light" {...props}></Icon>
