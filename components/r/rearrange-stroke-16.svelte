<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_11oy1hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h_11oy1hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rearrange-stroke-16" {...props}></Icon>
