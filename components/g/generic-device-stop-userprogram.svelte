<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wstt5lble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wstt5lble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-stop-userprogram" {...props}></Icon>
