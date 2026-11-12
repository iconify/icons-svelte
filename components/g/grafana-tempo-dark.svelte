<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0u0crbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0u0crbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-tempo-dark" {...props}></Icon>
