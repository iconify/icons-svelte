<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co3z9ob3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="co3z9ob3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:move-down" {...props}></Icon>
