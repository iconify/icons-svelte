<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxba6xbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yxba6xbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:exit" {...props}></Icon>
