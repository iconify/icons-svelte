<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrr_ohbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mrr_ohbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:compose-craft-light" {...props}></Icon>
