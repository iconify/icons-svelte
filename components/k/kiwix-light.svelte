<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgqiq1u1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgqiq1u1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kiwix-light" {...props}></Icon>
