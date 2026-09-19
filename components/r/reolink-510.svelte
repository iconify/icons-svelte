<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikbmv_b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikbmv_b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:reolink-510" {...props}></Icon>
