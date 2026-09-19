<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri_0_bfkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri_0_bfkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hexagon-alt" {...props}></Icon>
