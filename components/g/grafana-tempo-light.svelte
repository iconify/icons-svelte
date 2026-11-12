<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4wzr7bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h4wzr7bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-tempo-light" {...props}></Icon>
