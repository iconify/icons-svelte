<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaz65-dmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vaz65-dmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:minimize" {...props}></Icon>
