<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1q28xfug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1q28xfug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:propane-tank-outline" {...props}></Icon>
