<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttl4pbbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ttl4pbbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:crosshair2" {...props}></Icon>
