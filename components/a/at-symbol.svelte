<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiy71xbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uiy71xbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:at-symbol" {...props}></Icon>
