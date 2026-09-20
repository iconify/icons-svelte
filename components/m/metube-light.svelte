<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-a0zoblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-a0zoblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metube-light" {...props}></Icon>
