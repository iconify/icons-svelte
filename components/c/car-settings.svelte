<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lozdngyef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lozdngyef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-settings" {...props}></Icon>
