<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu0ij6bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fu0ij6bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:garlic-hub" {...props}></Icon>
