<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_er4bapv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_er4bapv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:focus-square-line" {...props}></Icon>
