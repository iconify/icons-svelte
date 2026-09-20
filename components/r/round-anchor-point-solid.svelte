<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9tipdjsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i9tipdjsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:round-anchor-point-solid" {...props}></Icon>
