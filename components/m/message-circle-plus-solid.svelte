<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzh__gl_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzh__gl_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-plus-solid" {...props}></Icon>
