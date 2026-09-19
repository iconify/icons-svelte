<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blhfqe0dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="blhfqe0dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:box-3d-stroke-16" {...props}></Icon>
