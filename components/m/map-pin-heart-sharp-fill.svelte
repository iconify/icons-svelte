<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esrqwyb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esrqwyb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:map-pin-heart-sharp-fill" {...props}></Icon>
