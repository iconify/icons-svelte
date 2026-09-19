<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcv25ub_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="jcv25ub_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:circle-o" {...props}></Icon>
