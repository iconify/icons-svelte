<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udfp8ebin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udfp8ebin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:race-car" {...props}></Icon>
