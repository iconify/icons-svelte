<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx_yp27iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mx_yp27iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:microphone-fill" {...props}></Icon>
