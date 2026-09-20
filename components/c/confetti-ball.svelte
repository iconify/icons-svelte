<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn_6w-26x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pn_6w-26x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:confetti-ball" {...props}></Icon>
