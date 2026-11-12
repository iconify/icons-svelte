<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j89cktuio.css';
import '../../css/r/rgvx_5b3k.css';
import '../../css/i/io-5labnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j89cktuio"/><path class="rgvx_5b3k"/><path class="io-5labnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-alerts-dashboard-dark" {...props}></Icon>
