<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb7gbybnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cb7gbybnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:car-battery-charging-remix" {...props}></Icon>
