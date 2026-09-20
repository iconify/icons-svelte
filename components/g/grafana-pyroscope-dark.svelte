<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpc8wfbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zpc8wfbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-pyroscope-dark" {...props}></Icon>
