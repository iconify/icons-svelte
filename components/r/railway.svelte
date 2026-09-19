<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peb9bwbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="peb9bwbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:railway" {...props}></Icon>
