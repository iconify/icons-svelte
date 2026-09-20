<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd9hy5b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pd9hy5b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:clock-solid" {...props}></Icon>
