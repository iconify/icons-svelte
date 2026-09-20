<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prh1_ibol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="prh1_ibol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-14-remix" {...props}></Icon>
