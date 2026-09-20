<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx--e_b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx--e_b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:potion" {...props}></Icon>
