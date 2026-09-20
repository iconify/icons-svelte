<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwq-6nbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwq-6nbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ciphermail" {...props}></Icon>
