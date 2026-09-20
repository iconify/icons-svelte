<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vscvyybmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vscvyybmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cone-shape-remix" {...props}></Icon>
