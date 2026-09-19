<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yui_j73uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yui_j73uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cart" {...props}></Icon>
