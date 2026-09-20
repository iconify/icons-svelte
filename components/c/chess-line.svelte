<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn72ziboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn72ziboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-line" {...props}></Icon>
