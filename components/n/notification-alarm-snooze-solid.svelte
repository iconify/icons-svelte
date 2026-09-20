<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8f87eb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8f87eb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:notification-alarm-snooze-solid" {...props}></Icon>
