<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjepf1bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjepf1bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-x" {...props}></Icon>
