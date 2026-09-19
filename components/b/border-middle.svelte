<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2kfsb4cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r2kfsb4cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:border-middle" {...props}></Icon>
