<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6a4ylago.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="s6a4ylago"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-dots" {...props}></Icon>
