<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw9ye5pbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zw9ye5pbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bowling-pin" {...props}></Icon>
