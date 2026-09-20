<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0er5_b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w0er5_b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:link" {...props}></Icon>
