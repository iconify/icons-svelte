<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yri5-ac-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yri5-ac-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:highlight" {...props}></Icon>
