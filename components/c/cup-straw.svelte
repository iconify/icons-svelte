<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvg1_8wii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cvg1_8wii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cup-straw" {...props}></Icon>
