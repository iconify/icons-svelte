<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l31hi9byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l31hi9byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:credit-card" {...props}></Icon>
