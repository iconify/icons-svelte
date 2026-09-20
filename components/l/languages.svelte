<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxj3mkv7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxj3mkv7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:languages" {...props}></Icon>
