<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnrnkda5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnrnkda5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ethernet-port-gloss" {...props}></Icon>
