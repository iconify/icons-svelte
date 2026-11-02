<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f06gkkbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f06gkkbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:headphone-line" {...props}></Icon>
