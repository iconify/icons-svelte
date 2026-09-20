<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqzeqtbqr.css';
import '../../css/f/fa6qugbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqzeqtbqr"/><path class="fa6qugbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ironcalc-dark" {...props}></Icon>
