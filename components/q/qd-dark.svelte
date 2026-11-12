<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krnj30b0h.css';
import '../../css/n/n8uyb4pln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="krnj30b0h"/><path class="n8uyb4pln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qd-dark" {...props}></Icon>
