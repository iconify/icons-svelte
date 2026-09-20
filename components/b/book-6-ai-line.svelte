<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a04ndx8hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a04ndx8hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-6-ai-line" {...props}></Icon>
