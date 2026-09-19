<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb9hnubnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="cb9hnubnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:bluetooth-connected" {...props}></Icon>
