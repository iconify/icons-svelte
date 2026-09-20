<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj749-bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wj749-bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:fave" {...props}></Icon>
