<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdp6nbcid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdp6nbcid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alarm-snooze-solid" {...props}></Icon>
