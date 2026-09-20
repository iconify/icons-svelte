<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9270-b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c9270-b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:globe-outline" {...props}></Icon>
