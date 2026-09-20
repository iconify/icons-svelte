<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpcz1bcnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpcz1bcnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fog-line" {...props}></Icon>
