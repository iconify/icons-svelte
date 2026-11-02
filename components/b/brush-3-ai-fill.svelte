<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxmqqxb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxmqqxb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-3-ai-fill" {...props}></Icon>
