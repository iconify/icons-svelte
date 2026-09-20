<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/firyb22yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="firyb22yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-bar-right" {...props}></Icon>
