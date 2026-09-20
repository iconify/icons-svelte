<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4q8hjbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f4q8hjbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:grid-three-up" {...props}></Icon>
