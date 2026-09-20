<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axwp7cbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axwp7cbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-floor-3" {...props}></Icon>
