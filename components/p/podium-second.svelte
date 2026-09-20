<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y41spbbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y41spbbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:podium-second" {...props}></Icon>
