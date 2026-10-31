<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp8n_7c6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k zp8n_7c6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dumpling-gloss" {...props}></Icon>
