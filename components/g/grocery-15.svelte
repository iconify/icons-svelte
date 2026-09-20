<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zscif1bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zscif1bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:grocery-15" {...props}></Icon>
