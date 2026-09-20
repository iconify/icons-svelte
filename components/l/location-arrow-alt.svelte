<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4fdc9b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4fdc9b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:location-arrow-alt" {...props}></Icon>
