<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1yxm6bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j1yxm6bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:minus" {...props}></Icon>
