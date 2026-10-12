<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqyl277ii.css';
import '../../css/m/mczjewvdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qqyl277ii"/><path class="mczjewvdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bot-sparkle-stroke-20" {...props}></Icon>
