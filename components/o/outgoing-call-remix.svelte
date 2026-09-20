<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdb3783_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cdb3783_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:outgoing-call-remix" {...props}></Icon>
