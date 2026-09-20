<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpn7p930p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qpn7p930p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:9router-dark" {...props}></Icon>
