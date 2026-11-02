<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clop3kblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clop3kblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hat-line" {...props}></Icon>
