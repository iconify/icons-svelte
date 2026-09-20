<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izm1r3bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izm1r3bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:font-line" {...props}></Icon>
