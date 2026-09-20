<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nela8-axq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nela8-axq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:logic-gate-xnor" {...props}></Icon>
