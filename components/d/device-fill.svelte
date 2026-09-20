<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmi_x69kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmi_x69kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:device-fill" {...props}></Icon>
