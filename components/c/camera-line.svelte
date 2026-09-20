<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k44dg_bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k44dg_bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camera-line" {...props}></Icon>
