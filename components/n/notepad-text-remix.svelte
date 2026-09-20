<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc6cptv2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fc6cptv2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:notepad-text-remix" {...props}></Icon>
