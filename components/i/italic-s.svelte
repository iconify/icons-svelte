<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orha0ukvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="orha0ukvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-s" {...props}></Icon>
