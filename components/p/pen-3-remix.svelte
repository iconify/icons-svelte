<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhdha2bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vhdha2bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pen-3-remix" {...props}></Icon>
