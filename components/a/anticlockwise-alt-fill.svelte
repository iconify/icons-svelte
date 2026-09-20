<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xekxvm7cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xekxvm7cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anticlockwise-alt-fill" {...props}></Icon>
