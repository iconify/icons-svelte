<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elzqj98pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elzqj98pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:asteroid" {...props}></Icon>
