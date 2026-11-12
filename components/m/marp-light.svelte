<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g22qdwbvx.css';
import '../../css/j/jahsuebty.css';
import '../../css/d/dcbk0ez8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g22qdwbvx"/><path class="jahsuebty"/><path class="dcbk0ez8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:marp-light" {...props}></Icon>
