<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soj2p2bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="soj2p2bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fork" {...props}></Icon>
