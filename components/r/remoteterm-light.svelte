<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urz7vu6vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="urz7vu6vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:remoteterm-light" {...props}></Icon>
