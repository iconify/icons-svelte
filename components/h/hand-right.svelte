<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_h17xb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_h17xb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:hand-right" {...props}></Icon>
