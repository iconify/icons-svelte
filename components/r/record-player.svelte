<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz999bcfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz999bcfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:record-player" {...props}></Icon>
