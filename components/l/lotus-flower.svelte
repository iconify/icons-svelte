<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zat54qabm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zat54qabm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lotus-flower" {...props}></Icon>
