<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_d1t5cfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e_d1t5cfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-arab-keheh-jeem" {...props}></Icon>
