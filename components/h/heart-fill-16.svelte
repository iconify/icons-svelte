<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3j1vl57g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p3j1vl57g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:heart-fill-16" {...props}></Icon>
