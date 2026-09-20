<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf--3zurr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf--3zurr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anniversary-line" {...props}></Icon>
