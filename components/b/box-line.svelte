<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbquv2bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbquv2bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:box-line" {...props}></Icon>
