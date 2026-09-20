<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sacp62b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sacp62b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-scatter-bubble-sharp" {...props}></Icon>
