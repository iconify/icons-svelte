<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqyn79ggl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vqyn79ggl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bone" {...props}></Icon>
