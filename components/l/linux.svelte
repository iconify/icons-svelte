<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j82880bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j82880bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:linux" {...props}></Icon>
