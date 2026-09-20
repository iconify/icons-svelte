<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j89cktuio.css';
import '../../css/t/tx20ehscf.css';
import '../../css/h/h4zt9xb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j89cktuio"/><path class="tx20ehscf"/><path class="h4zt9xb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-alerts-dashboard-dark" {...props}></Icon>
