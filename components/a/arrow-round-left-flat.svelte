<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3wdlk2ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d3wdlk2ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-round-left-flat" {...props}></Icon>
