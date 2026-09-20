<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc_bc1-ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc_bc1-ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:certificate-line" {...props}></Icon>
