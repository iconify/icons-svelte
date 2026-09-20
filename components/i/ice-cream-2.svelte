<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8cuki8wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x8cuki8wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:ice-cream-2" {...props}></Icon>
