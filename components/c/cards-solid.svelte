<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhxk1hsjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zhxk1hsjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cards-solid" {...props}></Icon>
