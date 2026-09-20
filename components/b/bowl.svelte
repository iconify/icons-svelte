<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a57te9brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a57te9brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bowl" {...props}></Icon>
