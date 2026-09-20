<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpa441bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jpa441bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grafana-dark" {...props}></Icon>
