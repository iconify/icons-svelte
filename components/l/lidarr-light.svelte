<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_0bz8nxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_0bz8nxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lidarr-light" {...props}></Icon>
