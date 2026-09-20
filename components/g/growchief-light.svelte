<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8x_9lbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p8x_9lbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:growchief-light" {...props}></Icon>
