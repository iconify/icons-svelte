<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wae5ng5nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wae5ng5nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:preset-ba" {...props}></Icon>
