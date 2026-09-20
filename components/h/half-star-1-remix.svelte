<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxyt2_hbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hxyt2_hbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:half-star-1-remix" {...props}></Icon>
