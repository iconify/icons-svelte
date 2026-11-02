<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwbvdccfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwbvdccfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:firefox-line" {...props}></Icon>
