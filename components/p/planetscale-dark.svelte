<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3e44p1-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o3e44p1-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:planetscale-dark" {...props}></Icon>
