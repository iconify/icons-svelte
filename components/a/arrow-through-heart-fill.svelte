<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmz5xyl5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kmz5xyl5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-through-heart-fill" {...props}></Icon>
