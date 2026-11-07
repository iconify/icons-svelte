<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt-6ugbcf.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wt-6ugbcf"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-chart-bold" {...props}></Icon>
