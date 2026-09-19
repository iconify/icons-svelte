<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncvg5reyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ncvg5reyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-107" {...props}></Icon>
