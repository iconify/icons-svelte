<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlzul8kzr.css';
import '../../css/s/sw83ssb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zlzul8kzr"/><path class="sw83ssb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bar-chart-square-stroke-20" {...props}></Icon>
