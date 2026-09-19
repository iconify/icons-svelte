<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug98l9j0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ug98l9j0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:heart" {...props}></Icon>
