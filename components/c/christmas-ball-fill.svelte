<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcpo2hbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcpo2hbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christmas-ball-fill" {...props}></Icon>
