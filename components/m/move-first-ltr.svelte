<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhua32s8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lhua32s8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:move-first-ltr" {...props}></Icon>
