<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhqhz4brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhqhz4brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:close" {...props}></Icon>
