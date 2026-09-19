<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knc22co5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="knc22co5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:play3" {...props}></Icon>
