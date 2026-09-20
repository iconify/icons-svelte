<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff8ok2bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff8ok2bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-6-ai-fill" {...props}></Icon>
