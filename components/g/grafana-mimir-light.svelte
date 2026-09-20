<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w39ea_d2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w39ea_d2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-mimir-light" {...props}></Icon>
