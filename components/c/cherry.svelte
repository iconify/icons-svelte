<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udo-y3bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udo-y3bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cherry" {...props}></Icon>
