<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx1la0w2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx1la0w2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-incompatible" {...props}></Icon>
