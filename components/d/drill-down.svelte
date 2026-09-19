<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1p_xpb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k1p_xpb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:drill-down" {...props}></Icon>
