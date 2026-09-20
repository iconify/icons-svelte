<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4_hh9bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y4_hh9bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-rewind-2" {...props}></Icon>
