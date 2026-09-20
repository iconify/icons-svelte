<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxkxh2bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxkxh2bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:confused-fill" {...props}></Icon>
