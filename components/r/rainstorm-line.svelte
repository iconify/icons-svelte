<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfgwkbcav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfgwkbcav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rainstorm-line" {...props}></Icon>
