<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyrk-tbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uyrk-tbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:compact-box-truck-with-greek-cross" {...props}></Icon>
