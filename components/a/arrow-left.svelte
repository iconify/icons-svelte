<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6s975bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y6s975bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-left" {...props}></Icon>
