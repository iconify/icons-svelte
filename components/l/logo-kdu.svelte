<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksggl2blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksggl2blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-kdu" {...props}></Icon>
