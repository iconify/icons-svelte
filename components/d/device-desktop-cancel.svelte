<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4l_q6qfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4l_q6qfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-cancel" {...props}></Icon>
