<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo82rec2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xo82rec2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:musescore" {...props}></Icon>
