<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzmn72bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yzmn72bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haproxy-cluster-manager-dark" {...props}></Icon>
