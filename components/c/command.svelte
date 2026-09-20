<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d792shgth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="d792shgth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:command" {...props}></Icon>
