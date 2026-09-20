<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hknlbeg7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hknlbeg7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-top-left-beside-arrow-top-right-above-arrow-bottom-left-beside-arrow-bottom-right" {...props}></Icon>
