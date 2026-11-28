<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkx5sub2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkx5sub2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:camera-x" {...props}></Icon>
