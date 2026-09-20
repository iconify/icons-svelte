<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij1ibzm9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij1ibzm9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bucket-off-outline" {...props}></Icon>
