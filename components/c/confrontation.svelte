<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elr-ebcxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elr-ebcxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:confrontation" {...props}></Icon>
