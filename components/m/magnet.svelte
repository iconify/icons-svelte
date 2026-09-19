<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ary-g3wyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ary-g3wyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:magnet" {...props}></Icon>
