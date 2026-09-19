<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu__fdcln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yu__fdcln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:move-up" {...props}></Icon>
