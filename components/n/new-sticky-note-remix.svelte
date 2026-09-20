<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl_um2bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sl_um2bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:new-sticky-note-remix" {...props}></Icon>
