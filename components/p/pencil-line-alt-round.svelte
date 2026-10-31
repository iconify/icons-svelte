<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh27scxld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh27scxld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-line-alt-round" {...props}></Icon>
