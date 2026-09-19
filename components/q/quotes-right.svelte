<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4zdoe4-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x4zdoe4-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:quotes-right" {...props}></Icon>
