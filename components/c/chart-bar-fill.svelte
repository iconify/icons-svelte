<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy9eo2bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fy9eo2bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chart-bar-fill" {...props}></Icon>
