<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1zfgxbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x1zfgxbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:coins-filled" {...props}></Icon>
