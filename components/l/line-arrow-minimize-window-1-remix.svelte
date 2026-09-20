<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqpcagbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jqpcagbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-minimize-window-1-remix" {...props}></Icon>
