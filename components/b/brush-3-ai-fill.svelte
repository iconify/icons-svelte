<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_s5fq2ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_s5fq2ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-3-ai-fill" {...props}></Icon>
