<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avekk7_9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avekk7_9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hdmi-port-fill" {...props}></Icon>
