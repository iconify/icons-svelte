<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fue3z8bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fue3z8bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:quiet-area" {...props}></Icon>
