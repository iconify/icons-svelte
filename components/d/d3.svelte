<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqnv71b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqnv71b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:d3" {...props}></Icon>
