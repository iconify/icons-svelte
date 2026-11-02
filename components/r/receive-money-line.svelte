<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2x3-6xto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2x3-6xto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:receive-money-line" {...props}></Icon>
