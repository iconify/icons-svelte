<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2p9e0byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f2p9e0byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:camping-tent-solid" {...props}></Icon>
