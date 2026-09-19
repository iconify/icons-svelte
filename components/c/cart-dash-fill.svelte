<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqbn5f49h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yqbn5f49h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cart-dash-fill" {...props}></Icon>
