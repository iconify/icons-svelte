<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxp0sccsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bxp0sccsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:heart-stroke-16" {...props}></Icon>
