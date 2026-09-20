<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9y1xtn3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9y1xtn3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:comentario-light" {...props}></Icon>
