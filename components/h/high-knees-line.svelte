<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fexe7_bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fexe7_bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:high-knees-line" {...props}></Icon>
