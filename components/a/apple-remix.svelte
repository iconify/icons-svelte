<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg72hbb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rg72hbb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:apple-remix" {...props}></Icon>
