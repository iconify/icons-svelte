<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2q56mb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l2q56mb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:maple-leaf" {...props}></Icon>
