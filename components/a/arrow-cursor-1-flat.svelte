<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1om9c1gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z1om9c1gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-cursor-1-flat" {...props}></Icon>
