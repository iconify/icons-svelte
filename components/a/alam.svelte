<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnddhgwsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dnddhgwsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:alam" {...props}></Icon>
