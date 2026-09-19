<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkex97b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pkex97b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:heart-fill" {...props}></Icon>
