<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idcd7i-ig.css';
import '../../css/o/o3-2211gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="idcd7i-ig"/><path class="o3-2211gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:character-fraction" {...props}></Icon>
