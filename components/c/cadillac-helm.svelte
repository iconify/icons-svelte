<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czm65ybep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czm65ybep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cadillac-helm" {...props}></Icon>
