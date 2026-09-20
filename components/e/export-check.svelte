<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swcuh7m3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="swcuh7m3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:export-check" {...props}></Icon>
