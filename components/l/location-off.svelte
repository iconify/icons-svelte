<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4jbm9q8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4jbm9q8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-off" {...props}></Icon>
