<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l93bm11qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l93bm11qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:building-container" {...props}></Icon>
