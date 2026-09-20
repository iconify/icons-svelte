<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrh5_9blm.css';
import '../../css/s/s4f0-m1sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrh5_9blm"/><path class="s4f0-m1sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:continuwuity-dark" {...props}></Icon>
