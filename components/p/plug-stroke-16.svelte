<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjeg9sbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zjeg9sbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plug-stroke-16" {...props}></Icon>
