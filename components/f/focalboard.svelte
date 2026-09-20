<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz8kk617p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bz8kk617p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:focalboard" {...props}></Icon>
