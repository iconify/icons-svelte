<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcg4c_nrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wcg4c_nrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-keyboard-previous-1-previous-keyboard-arrow-left" {...props}></Icon>
