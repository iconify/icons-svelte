<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xas180buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xas180buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frozen-block" {...props}></Icon>
