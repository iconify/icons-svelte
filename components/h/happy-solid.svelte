<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj7m1sbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yj7m1sbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:happy-solid" {...props}></Icon>
