<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxc68snwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxc68snwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:directions" {...props}></Icon>
