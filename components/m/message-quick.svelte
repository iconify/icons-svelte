<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw0emvb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw0emvb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-quick" {...props}></Icon>
