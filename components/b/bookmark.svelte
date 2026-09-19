<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl30ird_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wl30ird_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bookmark" {...props}></Icon>
