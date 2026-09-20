<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skl2_xb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="skl2_xb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:multiply" {...props}></Icon>
