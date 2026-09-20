<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aak4xjbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="aak4xjbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flash-1-remix" {...props}></Icon>
