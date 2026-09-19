<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy8n1abgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="wy8n1abgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:clubs-card" {...props}></Icon>
