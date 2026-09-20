<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiposv1sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hiposv1sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:c" {...props}></Icon>
