<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytvaq_byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ytvaq_byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gopeed-light" {...props}></Icon>
