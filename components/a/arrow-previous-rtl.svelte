<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of3k1s7ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="of3k1s7ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:arrow-previous-rtl" {...props}></Icon>
