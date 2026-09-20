<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r594i1p_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r594i1p_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:browser-bookmark-solid" {...props}></Icon>
