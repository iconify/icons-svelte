<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryx50ab7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ryx50ab7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:grin-beam" {...props}></Icon>
