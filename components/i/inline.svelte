<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyu-dyi9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yyu-dyi9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:inline" {...props}></Icon>
