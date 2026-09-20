<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy4x7jter.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wy4x7jter"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-fast-forward-2" {...props}></Icon>
