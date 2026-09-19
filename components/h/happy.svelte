<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7w-1fbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k7w-1fbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:happy" {...props}></Icon>
