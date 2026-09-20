<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax-zp5bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ax-zp5bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pen-draw" {...props}></Icon>
