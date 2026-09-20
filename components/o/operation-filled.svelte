<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6mslm3di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m6mslm3di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:operation-filled" {...props}></Icon>
