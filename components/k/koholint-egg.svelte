<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3gju4bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3gju4bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:koholint-egg" {...props}></Icon>
