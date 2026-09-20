<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9uj8bd6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r9uj8bd6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:next-rtl" {...props}></Icon>
