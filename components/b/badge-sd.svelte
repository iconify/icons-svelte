<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj2r2fivx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rj2r2fivx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:badge-sd" {...props}></Icon>
