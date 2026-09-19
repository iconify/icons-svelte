<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-2mgj25h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m-2mgj25h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:mug" {...props}></Icon>
