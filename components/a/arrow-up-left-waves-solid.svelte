<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwqfbdcyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwqfbdcyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-left-waves-solid" {...props}></Icon>
