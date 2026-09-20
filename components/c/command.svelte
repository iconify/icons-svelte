<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz1n0-axz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jz1n0-axz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:command" {...props}></Icon>
