<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw4srlbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw4srlbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-filament" {...props}></Icon>
