<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alssx_b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="alssx_b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bubbles4" {...props}></Icon>
