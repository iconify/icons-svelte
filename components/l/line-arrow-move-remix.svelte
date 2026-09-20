<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnfo_0tdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tnfo_0tdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-move-remix" {...props}></Icon>
