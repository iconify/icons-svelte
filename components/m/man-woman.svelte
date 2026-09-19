<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc5whdcgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gc5whdcgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:man-woman" {...props}></Icon>
