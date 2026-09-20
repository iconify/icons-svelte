<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pso53qx3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pso53qx3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chess-knight-remix" {...props}></Icon>
