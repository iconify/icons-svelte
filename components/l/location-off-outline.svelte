<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n093jabjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n093jabjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-off-outline" {...props}></Icon>
