<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1hudx9od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1hudx9od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:headset" {...props}></Icon>
