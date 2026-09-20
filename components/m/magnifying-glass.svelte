<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi5qd8jiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xi5qd8jiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:magnifying-glass" {...props}></Icon>
