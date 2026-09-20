<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl9coac9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl9coac9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mosaic-fill" {...props}></Icon>
