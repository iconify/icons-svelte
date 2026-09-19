<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaki46b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gaki46b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-exclamation-filled" {...props}></Icon>
