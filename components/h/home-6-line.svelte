<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfoxkd_6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfoxkd_6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-6-line" {...props}></Icon>
