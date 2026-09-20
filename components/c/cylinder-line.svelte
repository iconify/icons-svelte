<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp8zuho4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp8zuho4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cylinder-line" {...props}></Icon>
