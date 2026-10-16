<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrjnvkbuz.css';
import '../../css/x/xqit6kboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lrjnvkbuz"/><path class="xqit6kboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:negative-price-48" {...props}></Icon>
