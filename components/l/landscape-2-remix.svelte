<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zib-bfjpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zib-bfjpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:landscape-2-remix" {...props}></Icon>
