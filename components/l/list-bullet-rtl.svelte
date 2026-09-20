<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rif1eh3zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rif1eh3zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:list-bullet-rtl" {...props}></Icon>
