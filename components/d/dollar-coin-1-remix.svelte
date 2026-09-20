<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbe5hy7tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xbe5hy7tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dollar-coin-1-remix" {...props}></Icon>
