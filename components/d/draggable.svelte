<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2a3-308n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a2a3-308n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:draggable" {...props}></Icon>
