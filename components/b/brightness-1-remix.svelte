<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg517acka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cg517acka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:brightness-1-remix" {...props}></Icon>
