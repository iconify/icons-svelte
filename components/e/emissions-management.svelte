<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfj5y64ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gfj5y64ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:emissions-management" {...props}></Icon>
