<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5n1a1dep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p5n1a1dep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:arrow-cursor-move-remix" {...props}></Icon>
