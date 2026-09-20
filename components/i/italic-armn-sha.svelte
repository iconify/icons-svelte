<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud7qzlq2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ud7qzlq2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-armn-sha" {...props}></Icon>
