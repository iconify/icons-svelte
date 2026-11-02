<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzyj9h1zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzyj9h1zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:movie-2-line" {...props}></Icon>
