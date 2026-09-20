<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo9ej9zfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jo9ej9zfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-crossover-left" {...props}></Icon>
