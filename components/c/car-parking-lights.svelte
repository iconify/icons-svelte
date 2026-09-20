<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue9obbc0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue9obbc0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-parking-lights" {...props}></Icon>
