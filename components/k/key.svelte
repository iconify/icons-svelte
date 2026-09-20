<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfnvg26lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lfnvg26lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:key" {...props}></Icon>
