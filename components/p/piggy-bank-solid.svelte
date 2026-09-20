<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni3xbpbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ni3xbpbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:piggy-bank-solid" {...props}></Icon>
