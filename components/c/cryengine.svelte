<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gozsv_iaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gozsv_iaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cryengine" {...props}></Icon>
