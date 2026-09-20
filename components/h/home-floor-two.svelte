<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hus_4bcbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hus_4bcbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-floor-two" {...props}></Icon>
