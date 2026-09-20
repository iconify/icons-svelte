<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1h331y1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1h331y1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:controller-round-outline" {...props}></Icon>
