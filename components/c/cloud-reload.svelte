<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvny9pook.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rvny9pook"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cloud-reload" {...props}></Icon>
