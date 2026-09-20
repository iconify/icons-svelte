<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_a97_3xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_a97_3xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reference-point-bottom-left" {...props}></Icon>
