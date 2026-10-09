<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdl7-9bot.css';
import '../../css/x/xyt0ejbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qdl7-9bot"/><path class="xyt0ejbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-charging-20" {...props}></Icon>
