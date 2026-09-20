<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wybc3g-4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wybc3g-4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:apple" {...props}></Icon>
