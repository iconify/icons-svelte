<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_4panb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a_4panb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:level-none-rtl" {...props}></Icon>
