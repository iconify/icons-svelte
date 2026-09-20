<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7abg-bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7abg-bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:meh" {...props}></Icon>
