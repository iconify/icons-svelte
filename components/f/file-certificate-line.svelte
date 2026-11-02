<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hruluy_dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hruluy_dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-certificate-line" {...props}></Icon>
