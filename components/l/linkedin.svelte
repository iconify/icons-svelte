<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fte21iv7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fte21iv7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:linkedin" {...props}></Icon>
