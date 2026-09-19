<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9_r145xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9_r145xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:briefcase" {...props}></Icon>
