<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg01kfbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wg01kfbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pestle-mortar" {...props}></Icon>
