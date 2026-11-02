<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swy716zau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swy716zau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-line" {...props}></Icon>
