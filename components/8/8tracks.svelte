<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c610etbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="c610etbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:8tracks" {...props}></Icon>
