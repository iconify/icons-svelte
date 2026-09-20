<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybvsl1p_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybvsl1p_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid2-filled" {...props}></Icon>
