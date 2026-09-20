<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_dgfwbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u_dgfwbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:non-commercial-dollars-remix" {...props}></Icon>
