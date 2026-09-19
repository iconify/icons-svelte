<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywnk-4bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ywnk-4bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:protection-glasses" {...props}></Icon>
