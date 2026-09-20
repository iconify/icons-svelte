<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czmi4cb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czmi4cb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pangolin-light" {...props}></Icon>
