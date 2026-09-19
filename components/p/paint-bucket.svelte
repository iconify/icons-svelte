<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv6yotz8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cv6yotz8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:paint-bucket" {...props}></Icon>
