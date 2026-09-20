<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaw4gtbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yaw4gtbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:neo4j-light" {...props}></Icon>
