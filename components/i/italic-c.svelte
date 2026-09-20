<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjki1ptty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zjki1ptty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-c" {...props}></Icon>
