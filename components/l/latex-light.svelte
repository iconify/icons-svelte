<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwwggsb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nwwggsb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:latex-light" {...props}></Icon>
