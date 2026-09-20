<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yba2_offd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yba2_offd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:heart-solid" {...props}></Icon>
