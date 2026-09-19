<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_yv-xuoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_yv-xuoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:music-note" {...props}></Icon>
