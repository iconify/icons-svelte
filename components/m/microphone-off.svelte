<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkfb2-y9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkfb2-y9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:microphone-off" {...props}></Icon>
