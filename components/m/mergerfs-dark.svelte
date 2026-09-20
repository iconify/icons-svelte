<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlah1ebhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nlah1ebhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mergerfs-dark" {...props}></Icon>
