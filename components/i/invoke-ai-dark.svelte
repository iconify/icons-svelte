<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxbvolhhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yxbvolhhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoke-ai-dark" {...props}></Icon>
