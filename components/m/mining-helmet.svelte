<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3j6ezyms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3j6ezyms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mining-helmet" {...props}></Icon>
