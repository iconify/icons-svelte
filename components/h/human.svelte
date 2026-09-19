<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph659ubzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ph659ubzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:human" {...props}></Icon>
