<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsweexb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wsweexb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:graph-bar-increase-solid" {...props}></Icon>
