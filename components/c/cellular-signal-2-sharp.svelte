<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_0685brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_0685brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cellular-signal-2-sharp" {...props}></Icon>
