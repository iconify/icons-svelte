<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1bj2u4dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x1bj2u4dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:door-closed-fill" {...props}></Icon>
