<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4ubt_yrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4ubt_yrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-settings" {...props}></Icon>
