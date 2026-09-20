<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srcnhcb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="srcnhcb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-alloy" {...props}></Icon>
