<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x41tnzk-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x41tnzk-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-rewind" {...props}></Icon>
