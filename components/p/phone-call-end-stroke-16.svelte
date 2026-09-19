<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxhhfyb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oxhhfyb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-end-stroke-16" {...props}></Icon>
