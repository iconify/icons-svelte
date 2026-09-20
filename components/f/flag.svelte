<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy9xt0pmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vy9xt0pmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:flag" {...props}></Icon>
