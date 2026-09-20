<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnit63bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnit63bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:grids" {...props}></Icon>
