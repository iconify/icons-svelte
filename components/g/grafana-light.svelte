<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdsmi1bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vdsmi1bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-light" {...props}></Icon>
