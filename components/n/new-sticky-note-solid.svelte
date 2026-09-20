<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gby07cowi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gby07cowi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:new-sticky-note-solid" {...props}></Icon>
