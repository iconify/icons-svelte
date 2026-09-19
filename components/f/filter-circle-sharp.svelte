<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7qde211y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j7qde211y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:filter-circle-sharp" {...props}></Icon>
