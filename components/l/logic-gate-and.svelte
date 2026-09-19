<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0hdceb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p0hdceb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:logic-gate-and" {...props}></Icon>
