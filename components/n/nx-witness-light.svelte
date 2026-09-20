<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkmbvobhi.css';
import '../../css/f/fusmf-b6m.css';
import '../../css/l/ln0ym_was.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pkmbvobhi"/><path class="fusmf-b6m"/><path class="ln0ym_was"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nx-witness-light" {...props}></Icon>
