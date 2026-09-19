<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/navkkbhbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="navkkbhbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:map" {...props}></Icon>
