<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmi_rmt5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmi_rmt5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:check-line" {...props}></Icon>
