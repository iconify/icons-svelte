<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpx2bv8xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpx2bv8xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-4-line" {...props}></Icon>
