<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgm_fab8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgm_fab8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-location" {...props}></Icon>
