<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrtymebab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rrtymebab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-sm-stroke-12" {...props}></Icon>
