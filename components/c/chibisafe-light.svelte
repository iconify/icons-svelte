<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj6b63bfc.css';
import '../../css/j/jiywhnbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yj6b63bfc"/><path class="jiywhnbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chibisafe-light" {...props}></Icon>
