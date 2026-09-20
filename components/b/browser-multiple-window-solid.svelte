<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3xsz8tbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u3xsz8tbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:browser-multiple-window-solid" {...props}></Icon>
