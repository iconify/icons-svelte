<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eleh99bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eleh99bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-multiple-outline" {...props}></Icon>
