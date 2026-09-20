<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti9w0gblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti9w0gblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:facebook-solid" {...props}></Icon>
