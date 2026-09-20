<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk-neybtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xk-neybtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:lifering" {...props}></Icon>
