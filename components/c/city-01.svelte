<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/t/tysl7ubvg.css';
import '../../css/p/pytdb1oyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="tysl7ubvg"/><path class="pytdb1oyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:city-01" {...props}></Icon>
