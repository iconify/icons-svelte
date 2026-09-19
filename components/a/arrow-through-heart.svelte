<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq34fv2ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oq34fv2ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-through-heart" {...props}></Icon>
