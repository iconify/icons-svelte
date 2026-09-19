<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb8_k2byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wb8_k2byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:resizefull" {...props}></Icon>
