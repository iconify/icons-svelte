<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp8-r7b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp8-r7b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-download-outline" {...props}></Icon>
