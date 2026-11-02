<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd0p11bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd0p11bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:link-line" {...props}></Icon>
