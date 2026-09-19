<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4cxdgfzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="w4cxdgfzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:bitcoin" {...props}></Icon>
