<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peu9dxqux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="peu9dxqux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:deal-outline" {...props}></Icon>
