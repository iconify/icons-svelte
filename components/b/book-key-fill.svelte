<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-76r4lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq-76r4lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-key-fill" {...props}></Icon>
