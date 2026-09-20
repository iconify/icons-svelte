<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg9vbachl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rg9vbachl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:electric-cord-1" {...props}></Icon>
