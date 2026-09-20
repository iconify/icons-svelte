<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c96sl1brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c96sl1brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:3d-rotate-y-axis-remix" {...props}></Icon>
