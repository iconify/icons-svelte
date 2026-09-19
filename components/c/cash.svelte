<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5yuxmz6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i5yuxmz6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cash" {...props}></Icon>
