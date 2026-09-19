<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xie0vpbck.css';
import '../../css/r/rp66vlbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xie0vpbck"/><path class="rp66vlbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:closed-caption" {...props}></Icon>
