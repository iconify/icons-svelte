<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn0o6fb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn0o6fb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:linkedin-2-solid" {...props}></Icon>
