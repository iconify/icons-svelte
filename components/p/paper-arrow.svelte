<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8le6j7tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g8le6j7tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-arrow" {...props}></Icon>
