<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6vtb6xsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w6vtb6xsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chicken-grilled-stream-remix" {...props}></Icon>
