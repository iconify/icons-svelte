<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e80v1d7eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e80v1d7eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beach-bucket" {...props}></Icon>
