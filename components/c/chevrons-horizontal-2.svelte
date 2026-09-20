<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spfb3wbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spfb3wbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chevrons-horizontal-2" {...props}></Icon>
