<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llnjf5bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="llnjf5bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:qq" {...props}></Icon>
