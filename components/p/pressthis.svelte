<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6i0pt-4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6i0pt-4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:pressthis" {...props}></Icon>
