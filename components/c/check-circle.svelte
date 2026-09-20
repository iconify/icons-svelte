<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgt2snb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgt2snb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:check-circle" {...props}></Icon>
