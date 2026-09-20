<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk9p7gn2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rk9p7gn2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:flag-outline" {...props}></Icon>
