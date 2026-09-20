<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us8r5vb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="us8r5vb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:revolt" {...props}></Icon>
