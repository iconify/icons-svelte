<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf1p5q8zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xf1p5q8zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fire-dash" {...props}></Icon>
