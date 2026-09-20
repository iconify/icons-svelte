<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl7vwl9vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dl7vwl9vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mydrive" {...props}></Icon>
