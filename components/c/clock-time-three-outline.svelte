<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvefw0bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvefw0bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-three-outline" {...props}></Icon>
