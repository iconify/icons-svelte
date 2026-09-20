<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldmw-vboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldmw-vboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:location-compass-2-solid" {...props}></Icon>
