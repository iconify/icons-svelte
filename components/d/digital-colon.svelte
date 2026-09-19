<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k71cscbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":256};
const content = `<path class="k71cscbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital-colon" {...props}></Icon>
