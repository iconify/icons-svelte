<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixzxp9bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ixzxp9bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:keyboard-solid" {...props}></Icon>
