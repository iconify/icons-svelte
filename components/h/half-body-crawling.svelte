<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya7id6pwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ya7id6pwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:half-body-crawling" {...props}></Icon>
