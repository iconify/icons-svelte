<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imgt25i8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imgt25i8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-rke-dark" {...props}></Icon>
