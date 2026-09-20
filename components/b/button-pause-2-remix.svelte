<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_mbj4-zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r_mbj4-zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-pause-2-remix" {...props}></Icon>
