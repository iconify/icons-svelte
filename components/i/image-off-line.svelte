<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn4gjdhja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn4gjdhja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-off-line" {...props}></Icon>
