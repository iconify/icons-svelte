<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz9ljnb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qz9ljnb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:aumade" {...props}></Icon>
