<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxzmq3bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jxzmq3bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:political" {...props}></Icon>
