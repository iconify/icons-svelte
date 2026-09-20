<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_x7z-5qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e_x7z-5qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-crossover-left-cross-move-over-arrow-arrows-left" {...props}></Icon>
