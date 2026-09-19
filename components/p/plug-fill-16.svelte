<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs367gbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fs367gbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plug-fill-16" {...props}></Icon>
