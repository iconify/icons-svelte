<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny5pi-arz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny5pi-arz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-settings" {...props}></Icon>
