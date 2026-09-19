<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz0__bbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xz0__bbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-010" {...props}></Icon>
