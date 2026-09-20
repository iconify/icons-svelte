<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn3d9nbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kn3d9nbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:refresh-cancelled" {...props}></Icon>
