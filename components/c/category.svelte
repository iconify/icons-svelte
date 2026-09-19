<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p91smn2yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p91smn2yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:category" {...props}></Icon>
