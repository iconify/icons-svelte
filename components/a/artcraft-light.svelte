<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3j1mmhwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r3j1mmhwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:artcraft-light" {...props}></Icon>
