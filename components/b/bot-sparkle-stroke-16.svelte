<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3zxnib7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k3zxnib7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bot-sparkle-stroke-16" {...props}></Icon>
