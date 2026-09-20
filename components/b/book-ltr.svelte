<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkr-y0bjo.css';
import '../../css/p/pfpnh2nsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lkr-y0bjo"/><path class="pfpnh2nsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:book-ltr" {...props}></Icon>
