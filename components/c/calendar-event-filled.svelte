<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7v04kpsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7v04kpsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:calendar-event-filled" {...props}></Icon>
