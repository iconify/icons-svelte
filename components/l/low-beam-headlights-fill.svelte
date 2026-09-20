<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd0-3ctca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd0-3ctca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:low-beam-headlights-fill" {...props}></Icon>
