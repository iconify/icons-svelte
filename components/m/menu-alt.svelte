<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbx0ibcmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tbx0ibcmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:menu-alt" {...props}></Icon>
