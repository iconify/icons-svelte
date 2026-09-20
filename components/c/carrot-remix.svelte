<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtmtghbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gtmtghbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:carrot-remix" {...props}></Icon>
