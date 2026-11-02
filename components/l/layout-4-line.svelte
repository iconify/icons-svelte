<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rreqimzae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rreqimzae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-4-line" {...props}></Icon>
