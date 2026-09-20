<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxq9tlbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxq9tlbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pine-tree-multiple-outline" {...props}></Icon>
