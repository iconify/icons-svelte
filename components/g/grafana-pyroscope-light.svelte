<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/barzg96zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="barzg96zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-pyroscope-light" {...props}></Icon>
