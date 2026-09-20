<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssvx-7v6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssvx-7v6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coin-2-line" {...props}></Icon>
