<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjsav6i6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjsav6i6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-k3s-light" {...props}></Icon>
