<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar_sh6b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":432};
const content = `<path class="ar_sh6b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airplane" {...props}></Icon>
