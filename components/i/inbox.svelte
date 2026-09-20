<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb9-9z58s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb9-9z58s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:inbox" {...props}></Icon>
