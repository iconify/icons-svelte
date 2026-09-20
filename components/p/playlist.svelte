<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei1rwfbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei1rwfbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:playlist" {...props}></Icon>
