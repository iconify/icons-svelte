<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0e2o3btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w0e2o3btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hexagon-strip" {...props}></Icon>
