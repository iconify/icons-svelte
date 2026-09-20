<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieo8ob-ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieo8ob-ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-arrow-down" {...props}></Icon>
