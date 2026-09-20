<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv39e_b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gv39e_b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:puzzle-outline" {...props}></Icon>
