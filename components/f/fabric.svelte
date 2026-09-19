<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9r_svh8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":476,"height":512};
const content = `<path class="m9r_svh8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fabric" {...props}></Icon>
