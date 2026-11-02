<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l66dffbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l66dffbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-4-line" {...props}></Icon>
