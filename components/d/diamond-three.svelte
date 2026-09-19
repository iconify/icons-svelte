<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz5lfebzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uz5lfebzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:diamond-three" {...props}></Icon>
