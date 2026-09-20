<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8qgik12h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p8qgik12h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-bold" {...props}></Icon>
