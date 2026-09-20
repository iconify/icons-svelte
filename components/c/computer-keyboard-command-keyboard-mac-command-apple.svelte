<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u89zr7b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u89zr7b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-keyboard-command-keyboard-mac-command-apple" {...props}></Icon>
