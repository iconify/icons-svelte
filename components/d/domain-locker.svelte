<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgkrg8bvl.css';
import '../../css/r/r1m3whbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgkrg8bvl"/><path class="r1m3whbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-locker" {...props}></Icon>
