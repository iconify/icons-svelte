<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaj4x7b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uaj4x7b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-end-stroke-12" {...props}></Icon>
