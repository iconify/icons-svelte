<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feklsmb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="feklsmb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:mark-4" {...props}></Icon>
