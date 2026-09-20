<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp_uhacgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fp_uhacgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ombi-light" {...props}></Icon>
