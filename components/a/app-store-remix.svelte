<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xszjck75g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xszjck75g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:app-store-remix" {...props}></Icon>
