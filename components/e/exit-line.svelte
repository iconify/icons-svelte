<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp9f2qa0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp9f2qa0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exit-line" {...props}></Icon>
