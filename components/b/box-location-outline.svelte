<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etkz65bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etkz65bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-location-outline" {...props}></Icon>
