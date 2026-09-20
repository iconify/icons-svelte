<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tza8uod_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tza8uod_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:robot-vacuum-variant-off" {...props}></Icon>
