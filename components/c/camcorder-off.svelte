<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4eqseypw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4eqseypw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camcorder-off" {...props}></Icon>
