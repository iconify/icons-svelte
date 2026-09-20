<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upo6hjb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="upo6hjb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lungs-with-right-side-spots" {...props}></Icon>
