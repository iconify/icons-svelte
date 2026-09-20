<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ottw1fb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ottw1fb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:chat-add" {...props}></Icon>
