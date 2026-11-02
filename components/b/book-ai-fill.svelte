<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jweqvabsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jweqvabsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-ai-fill" {...props}></Icon>
