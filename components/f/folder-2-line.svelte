<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imx-i9zcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imx-i9zcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-2-line" {...props}></Icon>
