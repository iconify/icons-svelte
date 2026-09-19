<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvpai4bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvpai4bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-tree-alt" {...props}></Icon>
