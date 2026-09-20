<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knskys3gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knskys3gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mountain-line" {...props}></Icon>
