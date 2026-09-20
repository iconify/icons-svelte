<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha4ba9bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ha4ba9bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:reference-rtl" {...props}></Icon>
