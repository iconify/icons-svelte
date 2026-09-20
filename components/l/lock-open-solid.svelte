<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_-ave30o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r_-ave30o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:lock-open-solid" {...props}></Icon>
