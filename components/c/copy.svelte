<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od64xkb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="od64xkb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:copy" {...props}></Icon>
