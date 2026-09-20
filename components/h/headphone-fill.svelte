<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jggrwgbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jggrwgbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:headphone-fill" {...props}></Icon>
