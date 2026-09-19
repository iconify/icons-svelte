<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v72t6dbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v72t6dbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:alphabet-uppercase" {...props}></Icon>
