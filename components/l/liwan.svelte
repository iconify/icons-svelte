<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9ff30bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k9ff30bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:liwan" {...props}></Icon>
