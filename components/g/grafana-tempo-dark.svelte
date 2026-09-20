<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nik-3sbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nik-3sbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-tempo-dark" {...props}></Icon>
