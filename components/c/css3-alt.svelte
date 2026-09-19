<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m20u9ob6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m20u9ob6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:css3-alt" {...props}></Icon>
