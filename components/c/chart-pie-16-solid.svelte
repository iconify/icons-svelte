<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8wbxwy2x.css';
import '../../css/c/clxvp5dwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y8wbxwy2x"/><path class="clxvp5dwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chart-pie-16-solid" {...props}></Icon>
