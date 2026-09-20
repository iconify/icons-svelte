<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkvbhrbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkvbhrbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeipa-dark" {...props}></Icon>
