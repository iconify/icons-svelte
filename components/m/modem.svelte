<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypgdsmb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypgdsmb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:modem" {...props}></Icon>
