<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oll7jobqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":456,"height":464};
const content = `<path class="oll7jobqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:rotate-cw" {...props}></Icon>
