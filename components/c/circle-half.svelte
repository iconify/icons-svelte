<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf93g32nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf93g32nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:circle-half" {...props}></Icon>
