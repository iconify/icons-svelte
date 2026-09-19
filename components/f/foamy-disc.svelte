<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey91ksbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ey91ksbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:foamy-disc" {...props}></Icon>
