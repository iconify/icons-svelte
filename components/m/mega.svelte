<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8g8h_b3b.css';
import '../../css/p/p8n6moh0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="s8g8h_b3b"/><path class="p8n6moh0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mega" {...props}></Icon>
