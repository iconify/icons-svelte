<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw1jr1bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fw1jr1bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:projector-board-remix" {...props}></Icon>
