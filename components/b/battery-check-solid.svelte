<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0lcceblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0lcceblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-check-solid" {...props}></Icon>
