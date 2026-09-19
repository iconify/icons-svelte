<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2d7j5b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m2d7j5b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:easel2" {...props}></Icon>
