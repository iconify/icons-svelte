<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl4ov37_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cl4ov37_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:neko-light" {...props}></Icon>
