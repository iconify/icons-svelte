<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiv9skboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tiv9skboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-alloy-light" {...props}></Icon>
