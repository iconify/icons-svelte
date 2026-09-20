<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk_l8xbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk_l8xbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-bottom-solid" {...props}></Icon>
