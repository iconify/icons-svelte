<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2yfbmbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w2yfbmbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:recent-changes-rtl" {...props}></Icon>
