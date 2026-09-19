<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-lk33bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f-lk33bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:mesh-polygon" {...props}></Icon>
