<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei0prijnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ei0prijnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:filter-2-flat" {...props}></Icon>
