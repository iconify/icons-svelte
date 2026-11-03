<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8lwlo6og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u8lwlo6og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:adminer" {...props}></Icon>
