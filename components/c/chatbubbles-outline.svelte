<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri6_m1b9d.css';
import '../../css/v/v4jtutbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ri6_m1b9d"/><path class="v4jtutbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbubbles-outline" {...props}></Icon>
