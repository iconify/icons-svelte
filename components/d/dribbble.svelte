<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm7-icbdt.css';
import '../../css/f/fl5j57bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tm7-icbdt"/><path class="fl5j57bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:dribbble" {...props}></Icon>
