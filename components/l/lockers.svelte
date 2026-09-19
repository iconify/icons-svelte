<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpmiw8bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fpmiw8bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lockers" {...props}></Icon>
