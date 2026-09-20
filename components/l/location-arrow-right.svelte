<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mik8_3b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="mik8_3b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:location-arrow-right" {...props}></Icon>
