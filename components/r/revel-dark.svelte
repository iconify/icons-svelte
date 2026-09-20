<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bysezx81z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bysezx81z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:revel-dark" {...props}></Icon>
