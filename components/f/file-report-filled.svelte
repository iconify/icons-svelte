<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrhr15z4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrhr15z4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-report-filled" {...props}></Icon>
