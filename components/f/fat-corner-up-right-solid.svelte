<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p788krbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p788krbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-corner-up-right-solid" {...props}></Icon>
