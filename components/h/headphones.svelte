<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/patlzsgzl.css';
import '../../css/d/dvh2bwuis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="patlzsgzl"/><path class="dvh2bwuis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:headphones" {...props}></Icon>
