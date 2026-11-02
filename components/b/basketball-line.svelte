<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x26zr_bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x26zr_bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:basketball-line" {...props}></Icon>
