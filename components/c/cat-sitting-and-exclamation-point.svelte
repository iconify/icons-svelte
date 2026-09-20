<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec8qg8bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ec8qg8bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cat-sitting-and-exclamation-point" {...props}></Icon>
