<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhzkytj8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mhzkytj8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cursor-arrow-stroke-16" {...props}></Icon>
