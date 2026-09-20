<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6edfsb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j6edfsb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:drag-16" {...props}></Icon>
