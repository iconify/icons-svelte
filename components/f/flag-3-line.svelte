<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prv7dxb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prv7dxb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-3-line" {...props}></Icon>
