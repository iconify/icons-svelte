<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1aembgqz.css';
import '../../css/t/thhwdjbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c1aembgqz"/><path class="thhwdjbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:qwen" {...props}></Icon>
