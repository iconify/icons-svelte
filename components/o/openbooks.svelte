<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d15wwo3kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d15wwo3kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openbooks" {...props}></Icon>
