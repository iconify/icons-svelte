<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1w0_pbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="p1w0_pbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cube" {...props}></Icon>
