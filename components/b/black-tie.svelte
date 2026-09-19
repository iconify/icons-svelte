<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0x409cvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="u0x409cvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:black-tie" {...props}></Icon>
