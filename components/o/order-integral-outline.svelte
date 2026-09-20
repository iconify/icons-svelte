<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqim6db5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gqim6db5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:order-integral-outline" {...props}></Icon>
