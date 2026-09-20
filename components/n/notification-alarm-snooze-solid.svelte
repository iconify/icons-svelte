<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhn8o8b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uhn8o8b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:notification-alarm-snooze-solid" {...props}></Icon>
