<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc-3cybbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc-3cybbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:copyleft-solid" {...props}></Icon>
