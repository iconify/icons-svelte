<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9dxxwbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z9dxxwbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:index-card" {...props}></Icon>
