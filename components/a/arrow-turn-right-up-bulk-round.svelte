<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znn34tljo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znn34tljo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-right-up-bulk-round" {...props}></Icon>
