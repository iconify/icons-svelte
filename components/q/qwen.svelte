<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd4pa2b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pd4pa2b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:qwen" {...props}></Icon>
