<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znto94blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="znto94blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:arrow-move" {...props}></Icon>
