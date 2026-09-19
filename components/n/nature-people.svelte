<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1e6-lqkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="j1e6-lqkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:nature-people" {...props}></Icon>
