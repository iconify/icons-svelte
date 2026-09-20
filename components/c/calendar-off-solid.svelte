<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypw2v6byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypw2v6byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:calendar-off-solid" {...props}></Icon>
