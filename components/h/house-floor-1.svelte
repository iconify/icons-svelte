<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5unzbcza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5unzbcza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-floor-1" {...props}></Icon>
