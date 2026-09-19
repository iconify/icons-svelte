<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivgi5xbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1026};
const content = `<path class="ivgi5xbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bluetooth" {...props}></Icon>
