<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0r4fir6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b0r4fir6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-settings-2" {...props}></Icon>
