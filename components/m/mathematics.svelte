<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whq-7tb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="whq-7tb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:mathematics" {...props}></Icon>
