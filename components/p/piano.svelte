<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kel5pebld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kel5pebld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:piano" {...props}></Icon>
