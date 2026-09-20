<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwyqlacci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pwyqlacci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-bicycle" {...props}></Icon>
