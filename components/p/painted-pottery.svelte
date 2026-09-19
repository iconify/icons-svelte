<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eigw6bc8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eigw6bc8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:painted-pottery" {...props}></Icon>
