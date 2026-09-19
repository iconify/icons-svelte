<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x27_uqb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x27_uqb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:format-gallery" {...props}></Icon>
