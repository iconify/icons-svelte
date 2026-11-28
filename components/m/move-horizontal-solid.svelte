<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3w5q6brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3w5q6brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:move-horizontal-solid" {...props}></Icon>
