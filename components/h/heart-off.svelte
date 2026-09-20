<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akz0ez_3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="akz0ez_3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:heart-off" {...props}></Icon>
