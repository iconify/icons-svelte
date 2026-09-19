<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy19t-b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jy19t-b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:belt-buckles" {...props}></Icon>
