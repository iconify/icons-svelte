<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfv7tub0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfv7tub0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-code-filled" {...props}></Icon>
