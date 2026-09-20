<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9c_-qbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s9c_-qbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:building-construction" {...props}></Icon>
