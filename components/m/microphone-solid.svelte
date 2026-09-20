<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9_uklbjc.css';
import '../../css/p/pv-24ob8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t9_uklbjc"/><path class="pv-24ob8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:microphone-solid" {...props}></Icon>
