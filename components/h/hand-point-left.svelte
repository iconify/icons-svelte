<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4aagl8dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x4aagl8dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand-point-left" {...props}></Icon>
