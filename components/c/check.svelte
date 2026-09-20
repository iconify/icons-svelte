<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9vyexbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9vyexbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:check" {...props}></Icon>
