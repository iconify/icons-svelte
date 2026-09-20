<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6d9jv8kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j6d9jv8kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:align-right-16" {...props}></Icon>
