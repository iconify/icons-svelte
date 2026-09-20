<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy4eacc9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cy4eacc9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mouse-cursor-16" {...props}></Icon>
