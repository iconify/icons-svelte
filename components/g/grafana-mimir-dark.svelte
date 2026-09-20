<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbbm33x5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbbm33x5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-mimir-dark" {...props}></Icon>
