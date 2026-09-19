<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irdde39cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="irdde39cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-087" {...props}></Icon>
