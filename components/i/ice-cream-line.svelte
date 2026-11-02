<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj_7z6yeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj_7z6yeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ice-cream-line" {...props}></Icon>
