<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eto1u3blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eto1u3blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-check-round" {...props}></Icon>
