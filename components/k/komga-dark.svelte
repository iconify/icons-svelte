<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pof-r7bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pof-r7bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komga-dark" {...props}></Icon>
