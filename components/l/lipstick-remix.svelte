<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8bcq1tct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t8bcq1tct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lipstick-remix" {...props}></Icon>
