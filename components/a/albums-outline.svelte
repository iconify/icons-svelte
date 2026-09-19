<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j92jj3b8h.css';
import '../../css/w/wh8ezzf6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="j92jj3b8h"/><path class="wh8ezzf6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:albums-outline" {...props}></Icon>
