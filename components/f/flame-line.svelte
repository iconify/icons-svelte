<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j71gnfbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j71gnfbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flame-line" {...props}></Icon>
