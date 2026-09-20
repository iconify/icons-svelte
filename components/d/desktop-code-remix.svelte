<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zobuk4bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zobuk4bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:desktop-code-remix" {...props}></Icon>
