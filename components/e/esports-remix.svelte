<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw499_gnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dw499_gnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:esports-remix" {...props}></Icon>
