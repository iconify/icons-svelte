<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4prw-e6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4prw-e6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-ai-line" {...props}></Icon>
