<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mon9luzwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mon9luzwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-router" {...props}></Icon>
