<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lalxt3bxq.css';
import '../../css/t/tsc0xqbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lalxt3bxq"/><path class="tsc0xqbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:real-debrid" {...props}></Icon>
