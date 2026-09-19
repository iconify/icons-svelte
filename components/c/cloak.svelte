<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d35pi9b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d35pi9b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cloak" {...props}></Icon>
