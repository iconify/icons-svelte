<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktm_r_b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ktm_r_b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:oil" {...props}></Icon>
