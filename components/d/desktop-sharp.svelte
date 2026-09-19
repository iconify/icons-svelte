<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntn03pnxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntn03pnxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:desktop-sharp" {...props}></Icon>
